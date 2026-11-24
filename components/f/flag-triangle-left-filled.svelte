<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nho7-9bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nho7-9bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flag-triangle-left-filled" {...props}></Icon>
