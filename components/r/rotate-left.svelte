<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmdu012ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xmdu012ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rotate-left" {...props}></Icon>
