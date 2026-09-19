<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kidd-hbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kidd-hbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dlt" {...props}></Icon>
