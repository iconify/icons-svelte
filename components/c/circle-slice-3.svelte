<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_uv4jtqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_uv4jtqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:circle-slice-3" {...props}></Icon>
