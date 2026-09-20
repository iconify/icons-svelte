<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duza7ob8o.css';
import '../../css/j/jve4vacnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="duza7ob8o"/><path class="jve4vacnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-guard-open" {...props}></Icon>
