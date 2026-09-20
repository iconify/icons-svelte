<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c83vp7b4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c83vp7b4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:christian-cross-1-flat" {...props}></Icon>
