<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riei8-yoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":24};
const content = `<path class="riei8-yoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:multiplier-1" {...props}></Icon>
