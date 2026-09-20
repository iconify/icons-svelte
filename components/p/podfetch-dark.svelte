<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erhcsfbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erhcsfbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:podfetch-dark" {...props}></Icon>
