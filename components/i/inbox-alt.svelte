<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2zzkn9qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="f2zzkn9qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:inbox-alt" {...props}></Icon>
