<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3a2q10ee.css';
import '../../css/i/icrr06bxm.css';
import '../../css/t/tmgko40hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t3a2q10ee"/><path class="icrr06bxm"/><path class="tmgko40hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:office-48-bold" {...props}></Icon>
