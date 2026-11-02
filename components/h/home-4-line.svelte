<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl7lqyb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl7lqyb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-4-line" {...props}></Icon>
