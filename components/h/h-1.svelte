<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0h0z3pek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0h0z3pek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:h-1" {...props}></Icon>
