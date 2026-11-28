<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-v_dpbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-v_dpbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cursor-click" {...props}></Icon>
