<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffh0fmbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ffh0fmbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gxs" {...props}></Icon>
