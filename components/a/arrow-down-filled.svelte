<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq4no3lcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iq4no3lcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:arrow-down-filled" {...props}></Icon>
