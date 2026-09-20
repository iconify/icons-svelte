<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiap8ebun.css';
import '../../css/r/r_hb2znwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aiap8ebun"/><path class="r_hb2znwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-sublime" {...props}></Icon>
