<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvwqut9aq.css';
import '../../css/g/gooa6pv_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uvwqut9aq"/><path class="gooa6pv_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-swift" {...props}></Icon>
