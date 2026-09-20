<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlgfe8brk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dlgfe8brk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-tag" {...props}></Icon>
