<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrg0c1b_k.css';
import '../../css/d/d01u25bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrg0c1b_k"/><path class="d01u25bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-log-in" {...props}></Icon>
