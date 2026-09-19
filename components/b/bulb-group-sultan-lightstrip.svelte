<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxxt6ccfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxxt6ccfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-group-sultan-lightstrip" {...props}></Icon>
