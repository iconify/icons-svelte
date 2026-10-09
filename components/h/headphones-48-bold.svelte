<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrnf0ibmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yrnf0ibmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headphones-48-bold" {...props}></Icon>
