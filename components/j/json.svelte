<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s73lsdbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s73lsdbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:json" {...props}></Icon>
