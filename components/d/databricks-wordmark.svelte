<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7m4sz57z.css';
import '../../css/z/z-hzdxb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e7m4sz57z"/><path class="z-hzdxb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:databricks-wordmark" {...props}></Icon>
