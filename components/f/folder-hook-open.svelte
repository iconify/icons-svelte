<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48oh6fou.css';
import '../../css/v/vwhy-4s3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r48oh6fou"/><path class="vwhy-4s3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-hook-open" {...props}></Icon>
