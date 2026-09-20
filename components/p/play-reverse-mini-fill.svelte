<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb_juvaxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb_juvaxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-reverse-mini-fill" {...props}></Icon>
