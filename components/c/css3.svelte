<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzincubtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzincubtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:css3" {...props}></Icon>
