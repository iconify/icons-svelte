<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0tsj9bjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m0tsj9bjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-bottom-fill" {...props}></Icon>
