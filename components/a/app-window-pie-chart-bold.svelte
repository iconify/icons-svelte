<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6wc1bw2i.css';
import '../../css/h/h--yie27w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6wc1bw2i"/><path class="h--yie27w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-pie-chart-bold" {...props}></Icon>
