<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy_akccwx.css';
import '../../css/k/kohszfbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy_akccwx"/><path class="kohszfbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:funnel-x-filled" {...props}></Icon>
