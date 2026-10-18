<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu4hgabyh.css';
import '../../css/p/pajsys7wq.css';
import '../../css/c/clnf1dbfu.css';
import '../../css/q/qx_f1tive.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eu4hgabyh"/><path class="pajsys7wq"/><path class="clnf1dbfu"/><path class="qx_f1tive"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cooling-48-bold" {...props}></Icon>
