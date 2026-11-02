<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi7_ttbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi7_ttbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-plus-fill" {...props}></Icon>
