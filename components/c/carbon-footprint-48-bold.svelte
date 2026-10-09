<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2jt75bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d2jt75bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-footprint-48-bold" {...props}></Icon>
