<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnh6lfzed.css';
import '../../css/w/wax2jmrhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnh6lfzed"/><path class="wax2jmrhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-mouse" {...props}></Icon>
