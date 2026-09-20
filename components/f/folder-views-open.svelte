<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9dt8sqd.css';
import '../../css/n/n5fgqfbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="n5fgqfbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-views-open" {...props}></Icon>
