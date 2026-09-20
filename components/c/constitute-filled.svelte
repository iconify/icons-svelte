<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6hs4ob5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v6hs4ob5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:constitute-filled" {...props}></Icon>
