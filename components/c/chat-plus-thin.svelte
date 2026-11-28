<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crt23cceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="crt23cceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-plus-thin" {...props}></Icon>
