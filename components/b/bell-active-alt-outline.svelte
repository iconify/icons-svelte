<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1nw5935q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1nw5935q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:bell-active-alt-outline" {...props}></Icon>
