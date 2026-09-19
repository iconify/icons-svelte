<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie7e9dbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ie7e9dbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heartbeat-bold" {...props}></Icon>
