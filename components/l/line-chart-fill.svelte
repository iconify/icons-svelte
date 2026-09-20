<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz86vtb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz86vtb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:line-chart-fill" {...props}></Icon>
