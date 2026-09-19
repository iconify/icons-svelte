<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z28-l3b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z28-l3b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:candy-cane-solid" {...props}></Icon>
