<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwqcolm5j.css';
import '../../css/h/hp5qtbbru.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 wwqcolm5j"/><path class="clr-i-solid clr-i-solid-path-2 hp5qtbbru"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:microphone-solid" {...props}></Icon>
