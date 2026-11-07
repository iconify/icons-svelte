<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8qfwibcp.css';
import '../../css/l/lnqwqtb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8qfwibcp"/><path clip-rule="evenodd" class="lnqwqtb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:key-minimalistic-square-3-bold" {...props}></Icon>
