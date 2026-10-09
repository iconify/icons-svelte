<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-z0-wtpr.css';
import '../../css/c/c2yq94b2t.css';
import '../../css/j/jwhg0sbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e-z0-wtpr"/><path class="c2yq94b2t"/><path class="jwhg0sbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hospital-20" {...props}></Icon>
