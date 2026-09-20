<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnjf8b6m.css';
import '../../css/k/k9nz5w0-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><path class="k9nz5w0-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-interceptor" {...props}></Icon>
