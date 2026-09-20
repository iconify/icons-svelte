<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ki7-1hdyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ki7-1hdyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-small-fill" {...props}></Icon>
