<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0u5irbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0u5irbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message" {...props}></Icon>
