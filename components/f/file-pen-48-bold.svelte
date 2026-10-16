<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjdu4dbzy.css';
import '../../css/d/djhyfvqnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pjdu4dbzy"/><path class="djhyfvqnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-pen-48-bold" {...props}></Icon>
