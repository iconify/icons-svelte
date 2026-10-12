<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4q3a5btx.css';
import '../../css/x/x38o7w6oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4q3a5btx"/><path class="x38o7w6oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-stroke-20" {...props}></Icon>
