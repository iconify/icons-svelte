<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly3bwikbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly3bwikbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cup-updates-light" {...props}></Icon>
