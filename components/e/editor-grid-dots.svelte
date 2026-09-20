<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgix4xb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bgix4xb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:editor-grid-dots" {...props}></Icon>
