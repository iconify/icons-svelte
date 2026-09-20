<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6yqnk6da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h6yqnk6da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:document-edit" {...props}></Icon>
