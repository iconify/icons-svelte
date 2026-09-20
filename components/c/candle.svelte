<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-o237hvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-o237hvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:candle" {...props}></Icon>
