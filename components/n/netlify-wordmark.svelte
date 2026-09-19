<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9kb2bas.css';
import '../../css/l/l19uj4vqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dd9kb2bas"/><path class="l19uj4vqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:netlify-wordmark" {...props}></Icon>
