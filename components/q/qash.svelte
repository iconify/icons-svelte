<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea1-t_1gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ea1-t_1gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:qash" {...props}></Icon>
