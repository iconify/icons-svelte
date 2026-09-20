<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce6a4cb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce6a4cb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emergency-flashers-fill" {...props}></Icon>
