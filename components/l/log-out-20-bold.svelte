<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkfvnlevf.css';
import '../../css/m/mzr03n29o.css';
import '../../css/m/meohbdg3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qkfvnlevf"/><path class="mzr03n29o"/><path class="meohbdg3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:log-out-20-bold" {...props}></Icon>
