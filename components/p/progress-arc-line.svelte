<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l14lcgdye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l14lcgdye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-arc-line" {...props}></Icon>
