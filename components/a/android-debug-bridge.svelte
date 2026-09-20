<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbm8uzbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbm8uzbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:android-debug-bridge" {...props}></Icon>
