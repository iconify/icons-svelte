<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk-0nwoxu.css';
import '../../css/k/klrrfacgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nk-0nwoxu"/><path class="klrrfacgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dreamweaver" {...props}></Icon>
