<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb-1fbb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fb-1fbb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-fill" {...props}></Icon>
