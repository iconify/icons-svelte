<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmfg-je0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmfg-je0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plane-landing" {...props}></Icon>
