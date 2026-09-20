<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2t00mbrv.css';
import '../../css/z/z3y6h9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p2t00mbrv"/><path class="z3y6h9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-command" {...props}></Icon>
