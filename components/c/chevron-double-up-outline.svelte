<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn24i51gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn24i51gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chevron-double-up-outline" {...props}></Icon>
