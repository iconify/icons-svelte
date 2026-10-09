<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0224gbwy.css';
import '../../css/s/s149jjboe.css';
import '../../css/j/jqow3gbkz.css';
import '../../css/l/lb3olt71m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f0224gbwy"/><path class="s149jjboe"/><path class="jqow3gbkz"/><path class="lb3olt71m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gantry-crane-20-bold" {...props}></Icon>
