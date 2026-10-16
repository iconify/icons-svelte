<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfzjs4b6t.css';
import '../../css/y/y4dvfdc8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nfzjs4b6t"/><path class="y4dvfdc8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-detector-20-bold" {...props}></Icon>
