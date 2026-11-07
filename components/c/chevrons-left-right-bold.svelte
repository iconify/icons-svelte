<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5_nvnutr.css';
import '../../css/x/xe9j-trbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5_nvnutr"/><path class="xe9j-trbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-bold" {...props}></Icon>
