<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sufc7bcoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sufc7bcoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bar-chart-horizontal-end" {...props}></Icon>
