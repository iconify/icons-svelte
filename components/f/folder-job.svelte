<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud3_pd4ak.css';
import '../../css/r/rhohvnbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ud3_pd4ak"/><path class="rhohvnbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-job" {...props}></Icon>
