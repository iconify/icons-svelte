<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7w-cnw3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7w-cnw3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-1-line" {...props}></Icon>
