<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aml43npzb.css';
import '../../css/y/yf8s-acsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aml43npzb"/><path class="yf8s-acsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:pause" {...props}></Icon>
