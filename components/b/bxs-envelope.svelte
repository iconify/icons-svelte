<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_8c5nbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_8c5nbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-envelope" {...props}></Icon>
