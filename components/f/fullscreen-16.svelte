<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgu2i2bgi.css';
import '../../css/g/gyh2arbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgu2i2bgi"/><path clip-rule="evenodd" class="gyh2arbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:fullscreen-16" {...props}></Icon>
