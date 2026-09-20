<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nr28dlb2d.css';
import '../../css/f/f6a82rrqn.css';
import '../../css/b/b6enbdbml.css';
import '../../css/y/ywyqt1-eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nr28dlb2d"/><path class="f6a82rrqn"/><path class="b6enbdbml"/><path class="ywyqt1-eg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-circle-line-duotone" {...props}></Icon>
