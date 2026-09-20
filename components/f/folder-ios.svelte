<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wve-dxbgv.css';
import '../../css/k/kgcox8b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wve-dxbgv"/><path class="kgcox8b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ios" {...props}></Icon>
