<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx6v7i57h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cx6v7i57h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-down-linear" {...props}></Icon>
