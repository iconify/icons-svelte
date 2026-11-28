<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyr86z2_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jyr86z2_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-slash-thin" {...props}></Icon>
