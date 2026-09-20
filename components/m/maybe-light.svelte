<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scoavdblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scoavdblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maybe-light" {...props}></Icon>
