<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li0lmsb3e.css';
import '../../css/j/jnl6f4blr.css';
import '../../css/p/pycxazbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="li0lmsb3e"/><path class="jnl6f4blr"/><path class="pycxazbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chemical-plant-20" {...props}></Icon>
