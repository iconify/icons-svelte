<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq538skyr.css';
import '../../css/i/i54izb3il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iq538skyr"/><path class="i54izb3il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:netlify" {...props}></Icon>
