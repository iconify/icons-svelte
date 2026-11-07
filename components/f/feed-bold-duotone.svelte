<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmxpybrsb.css';
import '../../css/n/nghpb3cka.css';
import '../../css/u/uq14z1bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmxpybrsb"/><path class="nghpb3cka"/><path class="uq14z1bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:feed-bold-duotone" {...props}></Icon>
