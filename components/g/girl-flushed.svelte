<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md3g2pqyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="md3g2pqyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-flushed" {...props}></Icon>
