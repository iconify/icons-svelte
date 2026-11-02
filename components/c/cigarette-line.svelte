<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klvl_bb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klvl_bb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cigarette-line" {...props}></Icon>
