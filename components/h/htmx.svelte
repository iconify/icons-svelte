<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7xw2l-ms.css';
import '../../css/v/vp3r9_80y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e7xw2l-ms"/><path class="vp3r9_80y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:htmx" {...props}></Icon>
