<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3pbcab0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v3pbcab0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bring-to-front-light" {...props}></Icon>
