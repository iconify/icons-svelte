<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kldiywb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":460,"height":512};
const content = `<path class="kldiywb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:leaflet" {...props}></Icon>
