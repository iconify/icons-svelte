<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr4x_0bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr4x_0bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-left-circle" {...props}></Icon>
