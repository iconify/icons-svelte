<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxyn2mbuu.css';
import '../../css/l/l5s4u6bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jxyn2mbuu"/><path class="l5s4u6bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-pen-48-bold" {...props}></Icon>
