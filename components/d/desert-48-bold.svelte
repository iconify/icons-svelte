<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdhm6x6mb.css';
import '../../css/h/hlfitnjnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gdhm6x6mb"/><path class="hlfitnjnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desert-48-bold" {...props}></Icon>
