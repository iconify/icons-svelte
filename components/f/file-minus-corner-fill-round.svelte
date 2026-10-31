<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5a0avboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5a0avboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-minus-corner-fill-round" {...props}></Icon>
