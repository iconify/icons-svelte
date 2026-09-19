<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kod7n39qq.css';
import '../../css/s/sh8kg65pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kod7n39qq"/><path class="sh8kg65pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:klown" {...props}></Icon>
