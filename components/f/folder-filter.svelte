<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6_kf7bqk.css';
import '../../css/z/zywwkol3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l6_kf7bqk"/><path class="zywwkol3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-filter" {...props}></Icon>
