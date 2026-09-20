<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfzhtmbxu.css';
import '../../css/b/bmz0dzmey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfzhtmbxu"/><path class="bmz0dzmey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cardano-ada-line" {...props}></Icon>
