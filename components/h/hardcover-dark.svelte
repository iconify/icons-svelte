<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo7m7yb1l.css';
import '../../css/i/if85crc2z.css';
import '../../css/z/z-2dyjb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lo7m7yb1l"/><path class="if85crc2z"/><path class="z-2dyjb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hardcover-dark" {...props}></Icon>
