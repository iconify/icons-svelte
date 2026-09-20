<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouje6tb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouje6tb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-horizontal-start-sharp" {...props}></Icon>
