<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy-widoeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy-widoeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-increasing-line" {...props}></Icon>
