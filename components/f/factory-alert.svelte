<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3hc_y3xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3hc_y3xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:factory-alert" {...props}></Icon>
