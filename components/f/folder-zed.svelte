<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thk9tudjp.css';
import '../../css/n/ni5juab4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="thk9tudjp"/><path class="ni5juab4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-zed" {...props}></Icon>
