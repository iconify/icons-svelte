<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n36vjab5v.css';
import '../../css/c/cf167rjcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n36vjab5v"/><path class="cf167rjcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-node" {...props}></Icon>
