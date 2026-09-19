<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3igl-bgw.css';
import '../../css/t/taswdu53c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3igl-bgw"/><path class="taswdu53c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:camera-plus" {...props}></Icon>
