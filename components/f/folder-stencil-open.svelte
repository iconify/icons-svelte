<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hha2vm2py.css';
import '../../css/c/cdocj7brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hha2vm2py"/><path class="cdocj7brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-stencil-open" {...props}></Icon>
