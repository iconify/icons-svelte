<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww0y7wbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ww0y7wbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fedex-dark" {...props}></Icon>
