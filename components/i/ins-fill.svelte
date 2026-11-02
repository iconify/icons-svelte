<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-8_fb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-8_fb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ins-fill" {...props}></Icon>
