<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqpgh_bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqpgh_bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beephotos-dark" {...props}></Icon>
