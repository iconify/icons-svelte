<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjuv8i3nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjuv8i3nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:calendar-1-light" {...props}></Icon>
