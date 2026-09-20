<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq3a1xbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fq3a1xbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:oikos-dark" {...props}></Icon>
