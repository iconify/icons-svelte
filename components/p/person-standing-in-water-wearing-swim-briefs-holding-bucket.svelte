<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj9vsub_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uj9vsub_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-in-water-wearing-swim-briefs-holding-bucket" {...props}></Icon>
