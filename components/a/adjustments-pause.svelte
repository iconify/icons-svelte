<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0za66brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0za66brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-pause" {...props}></Icon>
