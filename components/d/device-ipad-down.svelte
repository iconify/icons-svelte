<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkeg8lbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkeg8lbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-down" {...props}></Icon>
