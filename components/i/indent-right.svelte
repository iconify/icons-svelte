<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl37isbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="fl37isbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:indent-right" {...props}></Icon>
