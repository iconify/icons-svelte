<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1i2kqxtp.css';
import '../../css/j/js0evub2c.css';
import '../../css/r/r_qwwvyaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p1i2kqxtp"/><path class="js0evub2c"/><path class="r_qwwvyaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hospital-48" {...props}></Icon>
