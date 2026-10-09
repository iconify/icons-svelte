<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciarmei3k.css';
import '../../css/n/nafa54a1z.css';
import '../../css/o/ofvhr7lmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ciarmei3k"/><path class="nafa54a1z"/><path class="ofvhr7lmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layers-48" {...props}></Icon>
