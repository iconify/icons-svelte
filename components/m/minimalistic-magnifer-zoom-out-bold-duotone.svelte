<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygw_60rm.css';
import '../../css/d/dzoyk5cfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="dzoyk5cfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-zoom-out-bold-duotone" {...props}></Icon>
