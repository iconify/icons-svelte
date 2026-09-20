<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqu14h6hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zqu14h6hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pacman-solid" {...props}></Icon>
