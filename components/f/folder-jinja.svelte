<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2gdbkbzv.css';
import '../../css/d/dn50i0run.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k2gdbkbzv"/><path class="dn50i0run"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-jinja" {...props}></Icon>
