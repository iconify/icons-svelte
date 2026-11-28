<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx0811s7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0811s7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:radio-off" {...props}></Icon>
