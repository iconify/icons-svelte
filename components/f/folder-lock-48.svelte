<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h68nt64um.css';
import '../../css/h/h2gpnpb6w.css';
import '../../css/w/wweom8b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h68nt64um"/><path class="h2gpnpb6w"/><path class="wweom8b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-lock-48" {...props}></Icon>
