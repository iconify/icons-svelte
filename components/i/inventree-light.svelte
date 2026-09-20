<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpb_-2b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rpb_-2b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inventree-light" {...props}></Icon>
