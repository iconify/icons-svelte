<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6mbt6uzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6mbt6uzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ease-curve-control-points" {...props}></Icon>
