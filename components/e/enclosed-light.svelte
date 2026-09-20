<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vluw-lfyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vluw-lfyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:enclosed-light" {...props}></Icon>
