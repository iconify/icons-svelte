<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw8qyw07p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw8qyw07p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pie-chart-2-line" {...props}></Icon>
