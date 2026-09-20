<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urvapf.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-28.css';
import '../../css/f/fill-to-0_3.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urvapf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:paint-drop-twotone" {...props}></Icon>
