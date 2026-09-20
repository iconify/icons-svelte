<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3qgmzeta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<path class="d3qgmzeta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:nest" {...props}></Icon>
