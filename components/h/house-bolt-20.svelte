<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz30y8b3r.css';
import '../../css/k/kqunv8bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dz30y8b3r"/><path class="kqunv8bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-bolt-20" {...props}></Icon>
