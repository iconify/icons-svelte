<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dglbhfbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dglbhfbwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cosmosdb-wordmark" {...props}></Icon>
