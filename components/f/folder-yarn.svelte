<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhg495fle.css';
import '../../css/z/zk3ynnbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nhg495fle"/><path class="zk3ynnbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-yarn" {...props}></Icon>
