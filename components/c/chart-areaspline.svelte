<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lso3-hbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lso3-hbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:chart-areaspline" {...props}></Icon>
