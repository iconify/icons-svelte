<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8n0i6b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i8n0i6b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:delete" {...props}></Icon>
