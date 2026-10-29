<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dckrksbvf.css';
import '../../css/d/dn9oi3j2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dckrksbvf wm-k"/><path class="dn9oi3j2f wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:heading" {...props}></Icon>
