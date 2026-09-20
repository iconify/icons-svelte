<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng8t65b2q.css';
import '../../css/r/rhohvnbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ng8t65b2q"/><path class="rhohvnbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-job-open" {...props}></Icon>
