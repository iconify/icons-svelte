<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpyz49q5o.css';
import '../../css/h/hyjsfrrwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gpyz49q5o"/><path class="hyjsfrrwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-blender-open" {...props}></Icon>
