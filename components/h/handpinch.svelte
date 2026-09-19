<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdh9m0b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="gdh9m0b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handpinch" {...props}></Icon>
