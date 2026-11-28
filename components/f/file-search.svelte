<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihke9ubmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihke9ubmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-search" {...props}></Icon>
