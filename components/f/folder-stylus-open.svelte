<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0c1nwb0d.css';
import '../../css/e/eu1xw2b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j0c1nwb0d"/><path class="eu1xw2b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-stylus-open" {...props}></Icon>
