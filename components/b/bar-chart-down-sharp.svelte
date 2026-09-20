<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2n4w53sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2n4w53sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-down-sharp" {...props}></Icon>
