<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixesgk-ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ixesgk-ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-fill-12" {...props}></Icon>
