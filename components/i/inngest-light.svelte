<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhuwacq1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":30};
const content = `<path clip-rule="evenodd" class="nhuwacq1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inngest-light" {...props}></Icon>
