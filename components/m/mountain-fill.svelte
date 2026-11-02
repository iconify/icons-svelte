<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uovd8rbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uovd8rbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-fill" {...props}></Icon>
