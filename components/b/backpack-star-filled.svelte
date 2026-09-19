<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3y4vm94d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3y4vm94d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:backpack-star-filled" {...props}></Icon>
