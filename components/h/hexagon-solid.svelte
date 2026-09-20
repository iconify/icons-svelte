<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxv_1p2jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxv_1p2jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:hexagon-solid" {...props}></Icon>
