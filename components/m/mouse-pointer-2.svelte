<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-z3s_rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-z3s_rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:mouse-pointer-2" {...props}></Icon>
