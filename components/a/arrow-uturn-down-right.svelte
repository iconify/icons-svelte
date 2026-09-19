<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axw8mbbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="axw8mbbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-uturn-down-right" {...props}></Icon>
