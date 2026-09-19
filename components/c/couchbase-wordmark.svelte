<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teeoa7uhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="teeoa7uhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:couchbase-wordmark" {...props}></Icon>
