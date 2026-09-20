<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teh_ozbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teh_ozbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-minus" {...props}></Icon>
