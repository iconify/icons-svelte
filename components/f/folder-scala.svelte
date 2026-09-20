<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajw-j-mwd.css';
import '../../css/r/r9utidyzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ajw-j-mwd"/><path class="r9utidyzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-scala" {...props}></Icon>
