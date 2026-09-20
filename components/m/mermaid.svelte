<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjxj44lwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="jjxj44lwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:mermaid" {...props}></Icon>
