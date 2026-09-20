<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7bi54bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7bi54bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:calculator" {...props}></Icon>
