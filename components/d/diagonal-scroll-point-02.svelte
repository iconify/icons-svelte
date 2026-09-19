<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/treytrb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="treytrb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diagonal-scroll-point-02" {...props}></Icon>
