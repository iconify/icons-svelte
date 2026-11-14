<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inu9bub3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inu9bub3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bazarr" {...props}></Icon>
