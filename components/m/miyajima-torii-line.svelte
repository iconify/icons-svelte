<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huapvubzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huapvubzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:miyajima-torii-line" {...props}></Icon>
