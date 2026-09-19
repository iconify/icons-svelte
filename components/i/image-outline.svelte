<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbia1d73n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbia1d73n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:image-outline" {...props}></Icon>
