<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp-oslbcg.css';
import '../../css/x/x1lrm4okj.css';
import '../../css/w/waeaixbmn.css';
import '../../css/i/ifw1webqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp-oslbcg"/><path class="x1lrm4okj"/><path class="waeaixbmn"/><path class="ifw1webqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-sad-bold-duotone" {...props}></Icon>
