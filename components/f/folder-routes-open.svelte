<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duza7ob8o.css';
import '../../css/e/edfie7bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="duza7ob8o"/><path class="edfie7bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-routes-open" {...props}></Icon>
