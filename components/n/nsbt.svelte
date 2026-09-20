<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-4pu_zsf.css';
import '../../css/i/iqgs3ioxp.css';
import '../../css/w/wwby37bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-4pu_zsf"/><path class="iqgs3ioxp"/><path class="wwby37bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nsbt" {...props}></Icon>
