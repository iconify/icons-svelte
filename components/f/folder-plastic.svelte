<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbnjf8b6m.css';
import '../../css/h/hogxnibkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fbnjf8b6m"/><path class="hogxnibkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-plastic" {...props}></Icon>
