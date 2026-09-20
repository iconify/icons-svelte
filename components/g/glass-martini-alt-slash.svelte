<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0_0sq8rl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_0sq8rl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:glass-martini-alt-slash" {...props}></Icon>
