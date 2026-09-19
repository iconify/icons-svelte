<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tirttc0dw.css';
import '../../css/b/bb02f9bqm.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 tirttc0dw"/><path class="bb02f9bqm clr-i-solid clr-i-solid-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:compass-solid" {...props}></Icon>
