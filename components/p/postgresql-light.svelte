<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq2todbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iq2todbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postgresql-light" {...props}></Icon>
