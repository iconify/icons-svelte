<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2sbulnjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c2sbulnjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-check-outline" {...props}></Icon>
