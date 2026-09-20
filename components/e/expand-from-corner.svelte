<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvllc_b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvllc_b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:expand-from-corner" {...props}></Icon>
