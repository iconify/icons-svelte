<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_fyibbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_fyibbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinwheel-2-fill" {...props}></Icon>
