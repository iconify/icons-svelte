<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oitekc77l.css';
import '../../css/m/m6f9qoawr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oitekc77l"/><path class="m6f9qoawr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-bottle-48" {...props}></Icon>
