<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4ie978fy.css';
import '../../css/s/si4ma1_ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u4ie978fy"/><path class="si4ma1_ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickstack" {...props}></Icon>
