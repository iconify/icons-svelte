<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbc2u206l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bbc2u206l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-cancelled-filled" {...props}></Icon>
