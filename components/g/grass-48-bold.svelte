<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6j5_ubif.css';
import '../../css/d/dpee-7beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o6j5_ubif"/><path class="dpee-7beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grass-48-bold" {...props}></Icon>
