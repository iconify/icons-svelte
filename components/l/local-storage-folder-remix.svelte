<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1qgo2r7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1qgo2r7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:local-storage-folder-remix" {...props}></Icon>
