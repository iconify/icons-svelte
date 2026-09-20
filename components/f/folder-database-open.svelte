<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8qgey2bj.css';
import '../../css/r/r-proe0do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b8qgey2bj"/><path class="r-proe0do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-database-open" {...props}></Icon>
