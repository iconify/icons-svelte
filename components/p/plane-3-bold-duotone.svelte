<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_ruqrb_t.css';
import '../../css/i/iyp-m0sxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_ruqrb_t"/><path class="iyp-m0sxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plane-3-bold-duotone" {...props}></Icon>
