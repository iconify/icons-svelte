<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6yv-o2yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6yv-o2yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exposure-fill" {...props}></Icon>
