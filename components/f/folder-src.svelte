<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz37bn_-f.css';
import '../../css/e/ejvzpugwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pz37bn_-f"/><path class="ejvzpugwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-src" {...props}></Icon>
