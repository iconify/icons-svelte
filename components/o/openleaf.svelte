<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbvxt794a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kbvxt794a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openleaf" {...props}></Icon>
