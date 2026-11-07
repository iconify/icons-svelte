<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwulmx5uf.css';
import '../../css/j/j07o9nb5s.css';
import '../../css/j/jlk36hbcb.css';
import '../../css/x/xcn7pebsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwulmx5uf"/><path class="j07o9nb5s"/><path class="jlk36hbcb"/><path class="xcn7pebsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-happy-bold-duotone" {...props}></Icon>
