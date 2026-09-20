<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdr4_oh2f.css';
import '../../css/k/kep5dhb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdr4_oh2f"/><path class="kep5dhb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-illustrator" {...props}></Icon>
