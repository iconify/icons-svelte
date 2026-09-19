<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfd5t0bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfd5t0bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-paper-plane" {...props}></Icon>
