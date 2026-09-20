<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyr2ydbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xyr2ydbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:block-1-flat" {...props}></Icon>
