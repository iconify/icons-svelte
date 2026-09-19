<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbd_w18hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbd_w18hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:password-pass" {...props}></Icon>
