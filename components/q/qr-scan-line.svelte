<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzfitt-vi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xzfitt-vi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:qr-scan-line" {...props}></Icon>
