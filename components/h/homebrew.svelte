<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u14sdab1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":397,"height":512};
const content = `<path clip-rule="evenodd" class="u14sdab1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:homebrew" {...props}></Icon>
