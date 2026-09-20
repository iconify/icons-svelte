<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh1y9gbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh1y9gbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flow-chart" {...props}></Icon>
