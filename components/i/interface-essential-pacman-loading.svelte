<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3xw2u99v.css';
import '../../css/f/fd-tsvb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3xw2u99v"/><path class="fd-tsvb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-pacman-loading" {...props}></Icon>
