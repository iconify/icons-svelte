<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-_fu0bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="h-_fu0bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:heartbeat" {...props}></Icon>
