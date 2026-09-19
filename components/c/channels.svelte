<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ps-obut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q7ps-obut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:channels" {...props}></Icon>
