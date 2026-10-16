<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lirqjjpoc.css';
import '../../css/r/rhxmnnb7m.css';
import '../../css/s/sri-3sbls.css';
import '../../css/i/i435drbbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lirqjjpoc"/><path class="rhxmnnb7m"/><path class="sri-3sbls"/><path class="i435drbbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lng-terminal-20" {...props}></Icon>
