<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5dcb7b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5dcb7b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-down-right-fill" {...props}></Icon>
