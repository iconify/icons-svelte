<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu1y0bbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu1y0bbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alert-circle-solid" {...props}></Icon>
