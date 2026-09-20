<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q80-_p5dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q80-_p5dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chevrons-left-right-ellipsis" {...props}></Icon>
