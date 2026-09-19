<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsp71pmgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsp71pmgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:elgato-ring-light" {...props}></Icon>
