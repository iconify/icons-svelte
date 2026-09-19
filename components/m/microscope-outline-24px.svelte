<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enw_gbbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enw_gbbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:microscope-outline-24px" {...props}></Icon>
