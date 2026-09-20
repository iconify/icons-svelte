<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfyb8iuwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfyb8iuwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rake-line" {...props}></Icon>
