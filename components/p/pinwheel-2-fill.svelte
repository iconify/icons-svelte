<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wih8tubvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wih8tubvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pinwheel-2-fill" {...props}></Icon>
