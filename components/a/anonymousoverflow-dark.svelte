<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie5ghf9ci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ie5ghf9ci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anonymousoverflow-dark" {...props}></Icon>
