<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmgn0uboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmgn0uboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gantry-crane" {...props}></Icon>
