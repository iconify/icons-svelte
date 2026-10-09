<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njz8i7bri.css';
import '../../css/i/i5ok5vt-f.css';
import '../../css/n/n_8e-wb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="njz8i7bri"/><path class="i5ok5vt-f"/><path class="n_8e-wb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-up-48-bold" {...props}></Icon>
