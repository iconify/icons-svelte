<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0djsxb9c.css';
import '../../css/r/r6hbisqks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="r6hbisqks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-desktop-open" {...props}></Icon>
