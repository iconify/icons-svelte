<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to19wsb8i.css';
import '../../css/v/vjo9wlbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to19wsb8i"/><path class="vjo9wlbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:meteor" {...props}></Icon>
