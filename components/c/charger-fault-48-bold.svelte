<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6y08ddso.css';
import '../../css/q/qky_02hhd.css';
import '../../css/y/y7680abmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j6y08ddso"/><path class="qky_02hhd"/><path class="y7680abmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-fault-48-bold" {...props}></Icon>
