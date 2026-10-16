<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaet4wb5s.css';
import '../../css/i/inqjblbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iaet4wb5s"/><path class="inqjblbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aspect-ratio-48-bold" {...props}></Icon>
