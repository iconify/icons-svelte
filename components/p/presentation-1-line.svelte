<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axr0p6pmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axr0p6pmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-1-line" {...props}></Icon>
