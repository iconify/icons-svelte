<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbr1am0tu.css';
import '../../css/t/tlsd_fw4s.css';
import '../../css/s/szs1icb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xbr1am0tu"/><path class="tlsd_fw4s"/><path class="szs1icb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-half-48" {...props}></Icon>
