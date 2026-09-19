<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyo09cc6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyo09cc6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-scan-text" {...props}></Icon>
