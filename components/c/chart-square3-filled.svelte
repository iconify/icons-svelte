<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri9akzb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ri9akzb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart-square3-filled" {...props}></Icon>
