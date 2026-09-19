<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5dkcracg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="d5dkcracg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrows-alt-v" {...props}></Icon>
