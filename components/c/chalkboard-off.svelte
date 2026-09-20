<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf7b16i3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf7b16i3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chalkboard-off" {...props}></Icon>
