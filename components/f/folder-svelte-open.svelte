<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsijkbbus.css';
import '../../css/a/ads0gkbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hsijkbbus"/><path class="ads0gkbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-svelte-open" {...props}></Icon>
