<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nolgd_b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nolgd_b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:impactstory" {...props}></Icon>
