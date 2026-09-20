<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kejaeac3h.css';
import '../../css/s/sbbfclb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kejaeac3h"/><path class="sbbfclb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:forgejo" {...props}></Icon>
