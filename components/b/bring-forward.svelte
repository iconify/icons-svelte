<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v15db6dui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v15db6dui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bring-forward" {...props}></Icon>
