<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvv10bauq.css';
import '../../css/h/h-_usl8fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zvv10bauq"/><path class="h-_usl8fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gear-48" {...props}></Icon>
