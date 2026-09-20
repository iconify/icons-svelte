<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqh3w-bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yqh3w-bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:floppy-disk-remix" {...props}></Icon>
