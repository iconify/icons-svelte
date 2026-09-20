<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0prf1r2a.css';
import '../../css/c/c1xpauj8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w0prf1r2a"/><path class="c1xpauj8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-lib" {...props}></Icon>
