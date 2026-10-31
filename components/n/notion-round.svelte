<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqxdm0s5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqxdm0s5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:notion-round" {...props}></Icon>
