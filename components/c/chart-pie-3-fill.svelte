<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwj58vb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwj58vb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-3-fill" {...props}></Icon>
