<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6ct7ybet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="y6ct7ybet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:id-filled" {...props}></Icon>
