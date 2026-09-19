<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-2d8gbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":607,"height":696};
const content = `<path class="w-2d8gbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:building" {...props}></Icon>
