<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flffaub2p.css';
import '../../css/h/hryfpbjgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="flffaub2p"/><path class="hryfpbjgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carabiner-48-bold" {...props}></Icon>
