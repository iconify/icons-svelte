<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfewowehb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfewowehb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ppc" {...props}></Icon>
