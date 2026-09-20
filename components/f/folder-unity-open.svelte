<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx2l3o9hm.css';
import '../../css/c/catkmrzgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gx2l3o9hm"/><path class="catkmrzgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-unity-open" {...props}></Icon>
