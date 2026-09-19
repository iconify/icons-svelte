<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx96-_bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx96-_bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bowl-food-outline" {...props}></Icon>
