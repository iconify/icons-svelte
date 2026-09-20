<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl0qbld8c.css';
import '../../css/d/dplt1qi1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sl0qbld8c"/><path class="dplt1qi1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-include" {...props}></Icon>
