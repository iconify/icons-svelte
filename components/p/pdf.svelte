<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmwvc3b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wmwvc3b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:pdf" {...props}></Icon>
