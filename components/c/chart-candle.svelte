<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coc-kh2xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="coc-kh2xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-candle" {...props}></Icon>
