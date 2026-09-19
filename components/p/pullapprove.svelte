<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imkvacbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="imkvacbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pullapprove" {...props}></Icon>
