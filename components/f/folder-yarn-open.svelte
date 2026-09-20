<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8r7eptda.css';
import '../../css/z/zk3ynnbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u8r7eptda"/><path class="zk3ynnbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-yarn-open" {...props}></Icon>
