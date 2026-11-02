<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wui7vkklb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wui7vkklb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-start-vertical-line" {...props}></Icon>
