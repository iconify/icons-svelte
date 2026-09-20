<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rog-zac5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rog-zac5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:candle-line" {...props}></Icon>
