<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfhi03nez.css';
import '../../css/j/jy4wz_42m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfhi03nez"/><path class="jy4wz_42m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:braces-bold-duotone" {...props}></Icon>
