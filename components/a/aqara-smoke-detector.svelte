<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg8uj_7zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg8uj_7zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-smoke-detector" {...props}></Icon>
