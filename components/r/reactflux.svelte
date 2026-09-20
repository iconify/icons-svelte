<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm7ss7bki.css';
import '../../css/g/gm0rcf1lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm7ss7bki"/><path class="gm0rcf1lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reactflux" {...props}></Icon>
