<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc00d4ghi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hc00d4ghi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:camera-rotate-bold" {...props}></Icon>
