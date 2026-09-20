<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd44gwpip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd44gwpip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:line-dashed" {...props}></Icon>
