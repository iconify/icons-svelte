<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs-mlfnuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rs-mlfnuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-next" {...props}></Icon>
