<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1i-5lhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="od1i-5lhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ars-technica-light" {...props}></Icon>
