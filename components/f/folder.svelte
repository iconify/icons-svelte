<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edz6g3fgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="edz6g3fgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:folder" {...props}></Icon>
