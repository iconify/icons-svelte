<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxe973c_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxe973c_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:remove-red-eye" {...props}></Icon>
