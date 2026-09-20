<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz2y_fbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz2y_fbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:game-fill" {...props}></Icon>
