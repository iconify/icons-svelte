<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6yuwkbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s6yuwkbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:file-deletion-solid" {...props}></Icon>
