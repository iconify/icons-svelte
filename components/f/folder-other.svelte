<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqh16pv3v.css';
import '../../css/u/u2z5ne2ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yqh16pv3v"/><path class="u2z5ne2ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-other" {...props}></Icon>
