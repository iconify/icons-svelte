<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spuyad3fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="spuyad3fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:payram-dark" {...props}></Icon>
