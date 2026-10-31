<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llhp5r44e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llhp5r44e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fast-forward-bulk-round" {...props}></Icon>
