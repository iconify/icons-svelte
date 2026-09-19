<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pin2mcbkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pin2mcbkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:hotdog-outline" {...props}></Icon>
