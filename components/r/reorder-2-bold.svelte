<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz49pjc-i.css';
import '../../css/b/bkgssdbwr.css';
import '../../css/m/mmwgdwotp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz49pjc-i"/><path class="bkgssdbwr"/><path class="mmwgdwotp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-2-bold" {...props}></Icon>
