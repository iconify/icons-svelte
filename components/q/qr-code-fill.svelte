<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr-x4e2ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rr-x4e2ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:qr-code-fill" {...props}></Icon>
