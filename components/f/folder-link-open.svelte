<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48oh6fou.css';
import '../../css/n/nwovjeb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r48oh6fou"/><path class="nwovjeb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-link-open" {...props}></Icon>
