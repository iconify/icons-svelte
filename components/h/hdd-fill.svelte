<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6d7zo6uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s6d7zo6uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hdd-fill" {...props}></Icon>
