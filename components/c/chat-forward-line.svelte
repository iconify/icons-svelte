<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfx6_cbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfx6_cbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-forward-line" {...props}></Icon>
