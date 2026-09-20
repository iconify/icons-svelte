<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95-ijf-n.css';
import '../../css/a/a98ziyr1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f95-ijf-n"/><path class="a98ziyr1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-scons" {...props}></Icon>
