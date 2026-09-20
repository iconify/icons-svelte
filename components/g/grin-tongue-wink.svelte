<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvla71nxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvla71nxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:grin-tongue-wink" {...props}></Icon>
