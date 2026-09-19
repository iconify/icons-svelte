<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rllujjb-s.css';
import '../../css/n/n36fbt-7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rllujjb-s"/><path class="n36fbt-7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-imdb" {...props}></Icon>
