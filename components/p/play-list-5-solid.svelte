<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2rjo44ao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f2rjo44ao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:play-list-5-solid" {...props}></Icon>
