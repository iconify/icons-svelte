<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lih_j9_oa.css';
import '../../css/d/debdggzbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lih_j9_oa"/><path class="debdggzbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-taskfile-open" {...props}></Icon>
