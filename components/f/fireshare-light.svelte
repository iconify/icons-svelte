<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9b_qv0ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l9b_qv0ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fireshare-light" {...props}></Icon>
