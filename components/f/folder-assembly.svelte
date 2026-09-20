<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg171ebhl.css';
import '../../css/u/uga_xo1ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hg171ebhl"/><path class="uga_xo1ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-assembly" {...props}></Icon>
