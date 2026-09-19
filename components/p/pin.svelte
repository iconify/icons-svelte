<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntpl853ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ntpl853ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:pin" {...props}></Icon>
