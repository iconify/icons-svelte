<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9v855hut.css';
import '../../css/y/y5mawg3ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c9v855hut"/><path class="y5mawg3ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:marker-geothermal-48" {...props}></Icon>
