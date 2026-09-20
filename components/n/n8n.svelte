<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-xvnbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":228,"height":120};
const content = `<path clip-rule="evenodd" class="wm-xvnbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:n8n" {...props}></Icon>
