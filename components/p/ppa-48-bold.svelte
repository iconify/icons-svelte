<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_pz3rxhk.css';
import '../../css/j/jhzmchb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="jhzmchb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-48-bold" {...props}></Icon>
