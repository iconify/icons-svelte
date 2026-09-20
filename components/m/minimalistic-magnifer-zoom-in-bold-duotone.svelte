<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygw_60rm.css';
import '../../css/o/oo3ilkkyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="oo3ilkkyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifer-zoom-in-bold-duotone" {...props}></Icon>
