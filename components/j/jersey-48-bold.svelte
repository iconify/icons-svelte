<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uayzpq5gn.css';
import '../../css/h/hokpvi8xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uayzpq5gn"/><path class="hokpvi8xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jersey-48-bold" {...props}></Icon>
