<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxxbg7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fxxbg7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graphhopper-light" {...props}></Icon>
