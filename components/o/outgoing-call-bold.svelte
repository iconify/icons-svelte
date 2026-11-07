<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-2vogrtb.css';
import '../../css/v/vglfn4bnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-2vogrtb"/><path class="vglfn4bnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:outgoing-call-bold" {...props}></Icon>
