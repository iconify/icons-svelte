<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgrtu-b6i.css';
import '../../css/y/yft263tla.css';
import '../../css/i/iqd64138m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgrtu-b6i"/><path class="yft263tla"/><path class="iqd64138m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammock-48" {...props}></Icon>
