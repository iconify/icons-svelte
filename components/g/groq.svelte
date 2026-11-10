<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa5z70b5c.css';
import '../../css/a/aa_dfybgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qa5z70b5c"/><path class="aa_dfybgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:groq" {...props}></Icon>
