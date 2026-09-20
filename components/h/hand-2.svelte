<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5f-vkbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5f-vkbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hand-2" {...props}></Icon>
