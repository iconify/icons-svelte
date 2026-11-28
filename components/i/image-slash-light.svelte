<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_e1e9t8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i_e1e9t8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-slash-light" {...props}></Icon>
