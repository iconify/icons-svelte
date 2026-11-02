<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt1uengkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt1uengkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-left-fill" {...props}></Icon>
