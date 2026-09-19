<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruemn0m6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ruemn0m6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:google-analytics" {...props}></Icon>
