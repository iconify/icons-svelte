<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0djsxb9c.css';
import '../../css/c/crdzj6byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="crdzj6byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-client-open" {...props}></Icon>
