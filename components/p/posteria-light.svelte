<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smlohmbtr.css';
import '../../css/u/u79s_5bes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="smlohmbtr"/><path class="u79s_5bes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posteria-light" {...props}></Icon>
