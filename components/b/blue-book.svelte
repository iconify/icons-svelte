<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/heic6riuh.css';
import '../../css/e/e3idh-b6l.css';
import '../../css/r/r3dusdbez.css';
import '../../css/e/enmu-w24f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="heic6riuh"/><path class="e3idh-b6l"/><path class="r3dusdbez"/><path class="enmu-w24f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:blue-book" {...props}></Icon>
