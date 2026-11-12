<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzzql6bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nzzql6bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jekyll-light" {...props}></Icon>
