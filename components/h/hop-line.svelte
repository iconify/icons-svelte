<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn6s0pb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn6s0pb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-line" {...props}></Icon>
