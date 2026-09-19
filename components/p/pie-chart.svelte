<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhrv8fevl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhrv8fevl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:pie-chart" {...props}></Icon>
