<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8sq8l6xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y8sq8l6xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-finger-drag-vertical-solid" {...props}></Icon>
