<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icrz6k5dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="icrz6k5dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-filter" {...props}></Icon>
