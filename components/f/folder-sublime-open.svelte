<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnxr3dbjd.css';
import '../../css/b/bkwkhrb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bnxr3dbjd"/><path class="bkwkhrb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-sublime-open" {...props}></Icon>
