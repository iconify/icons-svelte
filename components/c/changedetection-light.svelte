<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_4tm0byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_4tm0byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:changedetection-light" {...props}></Icon>
