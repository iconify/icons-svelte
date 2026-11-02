<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1t39q2tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1t39q2tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paper-fill" {...props}></Icon>
