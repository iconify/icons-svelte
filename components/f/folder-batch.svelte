<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiap8ebun.css';
import '../../css/l/lommj4luf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="lommj4luf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-batch" {...props}></Icon>
