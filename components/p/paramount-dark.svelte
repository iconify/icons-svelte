<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":118,"height":27};
const content = ``;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:paramount-dark" {...props}></Icon>
