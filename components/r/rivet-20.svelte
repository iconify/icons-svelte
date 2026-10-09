<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtkkymsak.css';
import '../../css/p/p3c5m7b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gtkkymsak"/><path class="p3c5m7b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rivet-20" {...props}></Icon>
