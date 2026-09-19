<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7ri8h3mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s7ri8h3mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:oax" {...props}></Icon>
