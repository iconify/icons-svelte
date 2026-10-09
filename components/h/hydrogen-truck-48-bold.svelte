<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avjgpmkfp.css';
import '../../css/d/dd3vljzrf.css';
import '../../css/r/rd9jhd3hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="avjgpmkfp"/><path class="dd3vljzrf"/><path class="rd9jhd3hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-truck-48-bold" {...props}></Icon>
