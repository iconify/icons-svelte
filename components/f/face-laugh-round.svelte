<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx89wlhpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx89wlhpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:face-laugh-round" {...props}></Icon>
