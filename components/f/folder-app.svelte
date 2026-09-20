<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95-ijf-n.css';
import '../../css/f/fxny2_b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="fxny2_b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-app" {...props}></Icon>
