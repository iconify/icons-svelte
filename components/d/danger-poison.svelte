<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrk-757mf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrk-757mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:danger-poison" {...props}></Icon>
