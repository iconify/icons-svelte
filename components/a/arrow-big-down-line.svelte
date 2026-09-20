<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exin_vbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exin_vbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-down-line" {...props}></Icon>
