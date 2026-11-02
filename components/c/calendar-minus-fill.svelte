<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjy2_xog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgjy2_xog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-minus-fill" {...props}></Icon>
