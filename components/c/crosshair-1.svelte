<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5la8q4rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y5la8q4rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:crosshair-1" {...props}></Icon>
