<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_25gqbls.css';
import '../../css/c/c8_pid-oz.css';
import '../../css/r/rr5ch2bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_25gqbls"/><path class="c8_pid-oz"/><path class="rr5ch2bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:info" {...props}></Icon>
