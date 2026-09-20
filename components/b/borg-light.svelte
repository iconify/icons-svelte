<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsmmuf2ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsmmuf2ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:borg-light" {...props}></Icon>
