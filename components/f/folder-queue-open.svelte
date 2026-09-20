<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0djsxb9c.css';
import '../../css/m/m95mj6b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z0djsxb9c"/><path class="m95mj6b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-queue-open" {...props}></Icon>
