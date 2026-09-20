<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za41vfpmx.css';
import '../../css/d/dfdvapbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="za41vfpmx"/><path class="dfdvapbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2000" {...props}></Icon>
