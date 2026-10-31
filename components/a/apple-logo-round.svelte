<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf2-8lbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2-8lbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:apple-logo-round" {...props}></Icon>
