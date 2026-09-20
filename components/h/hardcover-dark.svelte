<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psqwx_-ti.css';
import '../../css/i/if85crc2z.css';
import '../../css/m/mc-ix1blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="psqwx_-ti"/><path class="if85crc2z"/><path class="mc-ix1blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hardcover-dark" {...props}></Icon>
