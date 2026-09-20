<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzh5w72co.css';
import '../../css/i/ixz4scd6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tzh5w72co"/><path class="ixz4scd6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mercurial-open" {...props}></Icon>
