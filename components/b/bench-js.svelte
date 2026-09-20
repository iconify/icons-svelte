<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m49lunb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m49lunb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:bench-js" {...props}></Icon>
