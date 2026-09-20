<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mav9q8bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mav9q8bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:add-row" {...props}></Icon>
