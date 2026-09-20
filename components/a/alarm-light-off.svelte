<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kip2eh77n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kip2eh77n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alarm-light-off" {...props}></Icon>
