<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-3ob9bho.css';
import '../../css/j/j6vszybch.css';
import '../../css/t/tlsuctbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-3ob9bho wm-shadow"/><path class="j6vszybch wm-k"/><path class="tlsuctbpn wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-down-right" {...props}></Icon>
