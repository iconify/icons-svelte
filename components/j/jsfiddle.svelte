<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w10fp8n8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w10fp8n8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jsfiddle" {...props}></Icon>
