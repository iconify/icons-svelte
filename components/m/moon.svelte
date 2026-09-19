<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xga62ygic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xga62ygic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:moon" {...props}></Icon>
