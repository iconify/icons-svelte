<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eewd2xbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eewd2xbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mqtt" {...props}></Icon>
