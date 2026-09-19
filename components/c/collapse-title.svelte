<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkz67rbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vkz67rbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:collapse-title" {...props}></Icon>
