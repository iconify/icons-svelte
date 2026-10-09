<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcp6u-oop.css';
import '../../css/e/ee8dj_rhy.css';
import '../../css/o/on5c6nbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qcp6u-oop"/><path class="ee8dj_rhy"/><path class="on5c6nbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:price-down-48-bold" {...props}></Icon>
