<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpbwr0yxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpbwr0yxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-3-line" {...props}></Icon>
