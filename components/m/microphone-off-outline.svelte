<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiaxfabid.css';
import '../../css/d/dpr9gubjx.css';
import '../../css/x/x0-csbbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiaxfabid"/><path clip-rule="evenodd" class="dpr9gubjx"/><path class="x0-csbbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:microphone-off-outline" {...props}></Icon>
