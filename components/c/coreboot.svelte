<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7_m8xdwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7_m8xdwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:coreboot" {...props}></Icon>
