<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p36knsbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p36knsbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nodecast-tv" {...props}></Icon>
