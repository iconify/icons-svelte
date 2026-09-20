<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p295tee_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="p295tee_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:amusement-park-11" {...props}></Icon>
