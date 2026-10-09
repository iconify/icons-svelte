<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arf8ercmz.css';
import '../../css/w/wmf5h3zqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="arf8ercmz"/><path class="wmf5h3zqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrows-vertical-48-bold" {...props}></Icon>
