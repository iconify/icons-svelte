<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aygw_60rm.css';
import '../../css/r/r9znqobzq.css';
import '../../css/c/czuk_uaey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aygw_60rm"/><path clip-rule="evenodd" class="r9znqobzq"/><path class="czuk_uaey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-zoom-in-bold-duotone" {...props}></Icon>
