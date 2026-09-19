<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1fx9w8jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1fx9w8jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:influxdata" {...props}></Icon>
