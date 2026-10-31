<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwqsjcb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqsjcb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-days-round" {...props}></Icon>
