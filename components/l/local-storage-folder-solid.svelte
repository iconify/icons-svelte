<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2l4x0b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l2l4x0b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:local-storage-folder-solid" {...props}></Icon>
