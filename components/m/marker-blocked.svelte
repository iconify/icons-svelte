<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktdlbrk9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktdlbrk9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:marker-blocked" {...props}></Icon>
