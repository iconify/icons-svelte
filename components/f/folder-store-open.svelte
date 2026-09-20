<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9dt8sqd.css';
import '../../css/m/mrww_9xen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="mrww_9xen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-store-open" {...props}></Icon>
