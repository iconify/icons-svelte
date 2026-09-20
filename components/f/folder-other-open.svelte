<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi9dt8sqd.css';
import '../../css/u/u2z5ne2ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vi9dt8sqd"/><path class="u2z5ne2ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-other-open" {...props}></Icon>
