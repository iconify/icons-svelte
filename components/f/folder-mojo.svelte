<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqh16pv3v.css';
import '../../css/u/u_htwfjih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yqh16pv3v"/><path class="u_htwfjih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mojo" {...props}></Icon>
