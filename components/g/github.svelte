<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdptjablm.css';
import '../../css/n/nsdrsoimu.css';
import '../../css/l/l88o95l5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="tdptjablm"><path clip-rule="evenodd" class="nsdrsoimu"/><path class="l88o95l5d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:github" {...props}></Icon>
