<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwfex86-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cwfex86-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:group" {...props}></Icon>
