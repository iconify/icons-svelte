<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maehpb1hl.css';
import '../../css/o/ouy5zcixh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="maehpb1hl"/><path class="ouy5zcixh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mytview" {...props}></Icon>
