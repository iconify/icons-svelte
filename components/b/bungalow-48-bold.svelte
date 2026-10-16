<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqam2b2u.css';
import '../../css/l/liw2htv9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mrqam2b2u"/><path class="liw2htv9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bungalow-48-bold" {...props}></Icon>
