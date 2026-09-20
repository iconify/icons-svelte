<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr0hlbc2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr0hlbc2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monitor-bold" {...props}></Icon>
