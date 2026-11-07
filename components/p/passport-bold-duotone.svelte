<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dek9bkq9j.css';
import '../../css/f/fsclr0dbg.css';
import '../../css/h/hsyg8kbzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dek9bkq9j"/><path clip-rule="evenodd" class="fsclr0dbg"/><path class="hsyg8kbzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:passport-bold-duotone" {...props}></Icon>
