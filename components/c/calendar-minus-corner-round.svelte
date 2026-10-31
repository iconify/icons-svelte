<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug7e57byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug7e57byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-minus-corner-round" {...props}></Icon>
