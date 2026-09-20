<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naa-2hjrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="naa-2hjrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:double-quote-sans-right" {...props}></Icon>
