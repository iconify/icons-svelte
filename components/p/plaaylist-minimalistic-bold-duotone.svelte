<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n416od3sq.css';
import '../../css/s/smfmp7bbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n416od3sq"/><path class="smfmp7bbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plaaylist-minimalistic-bold-duotone" {...props}></Icon>
