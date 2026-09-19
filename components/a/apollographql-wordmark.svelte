<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwickvboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jwickvboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apollographql-wordmark" {...props}></Icon>
