<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsjky8-vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":429.02,"height":429.02,"left":116,"top":34.49};
const content = `<path class="dsjky8-vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mastra" {...props}></Icon>
