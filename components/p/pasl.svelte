<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hozfo_wji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hozfo_wji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pasl" {...props}></Icon>
