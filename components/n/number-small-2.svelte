<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkh4z0b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vkh4z0b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-2" {...props}></Icon>
