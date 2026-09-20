<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itx84tljk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="itx84tljk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:last-fm" {...props}></Icon>
