<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khz89abja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="khz89abja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box" {...props}></Icon>
