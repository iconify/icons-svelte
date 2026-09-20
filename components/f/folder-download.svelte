<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz37bn_-f.css';
import '../../css/g/gnnj1jfmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pz37bn_-f"/><path class="gnnj1jfmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-download" {...props}></Icon>
