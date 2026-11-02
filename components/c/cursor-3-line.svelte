<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swkw51pea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swkw51pea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cursor-3-line" {...props}></Icon>
