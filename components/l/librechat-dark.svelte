<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcm3g6b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcm3g6b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librechat-dark" {...props}></Icon>
