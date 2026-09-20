<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0sdg2bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0sdg2bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hoppscotch-dark" {...props}></Icon>
