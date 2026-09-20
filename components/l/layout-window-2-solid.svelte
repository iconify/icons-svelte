<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6xi-86mu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x6xi-86mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-2-solid" {...props}></Icon>
