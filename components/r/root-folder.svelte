<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm7aqnb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zm7aqnb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:root-folder" {...props}></Icon>
