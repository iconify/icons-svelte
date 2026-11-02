<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vphqdebod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vphqdebod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-pen-line" {...props}></Icon>
