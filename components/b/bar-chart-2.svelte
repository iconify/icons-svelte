<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4wt8hb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4wt8hb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bar-chart-2" {...props}></Icon>
