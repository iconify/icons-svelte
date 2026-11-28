<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-q82zjom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-q82zjom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flip-horizontal" {...props}></Icon>
