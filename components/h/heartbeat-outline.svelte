<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfg5flbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xfg5flbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heartbeat-outline" {...props}></Icon>
