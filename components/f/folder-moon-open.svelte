<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48oh6fou.css';
import '../../css/u/u86f3_xou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r48oh6fou"/><path class="u86f3_xou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-moon-open" {...props}></Icon>
