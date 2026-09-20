<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpi5w_ocz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpi5w_ocz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-plus" {...props}></Icon>
