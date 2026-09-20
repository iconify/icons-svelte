<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gszlt-bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gszlt-bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:enphase" {...props}></Icon>
