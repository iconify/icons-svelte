<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk9zn-beg.css';
import '../../css/o/o9cgf80vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk9zn-beg"/><path class="o9cgf80vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rauthy-dark" {...props}></Icon>
