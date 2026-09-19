<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0g0kyhvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0g0kyhvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-vk" {...props}></Icon>
