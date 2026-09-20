<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsijkbbus.css';
import '../../css/m/m3bl0tblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hsijkbbus"/><path class="m3bl0tblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mjml-open" {...props}></Icon>
