<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di-r0pzwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di-r0pzwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-g4" {...props}></Icon>
