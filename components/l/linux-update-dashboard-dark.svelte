<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbrrtibxz.css';
import '../../css/i/i5rwfcc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bbrrtibxz"/><path class="i5rwfcc2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linux-update-dashboard-dark" {...props}></Icon>
