<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njq8_c_rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="njq8_c_rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notifiarr-dark" {...props}></Icon>
