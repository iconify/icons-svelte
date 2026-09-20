<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfne-sg-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfne-sg-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bar-chart-horizontal-line" {...props}></Icon>
