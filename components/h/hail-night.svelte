<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq4d_iynl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nq4d_iynl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hail-night" {...props}></Icon>
