<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv2f5p14q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv2f5p14q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:broken-link" {...props}></Icon>
