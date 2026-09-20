<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e29zf5bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e29zf5bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:network-off-line" {...props}></Icon>
