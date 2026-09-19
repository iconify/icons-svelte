<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srt32fbam.css';
import '../../css/s/s76ldob_q.css';
import '../../css/b/bp242uqss.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-outline clr-i-outline-path-1 srt32fbam"/><path class="clr-i-outline clr-i-outline-path-2 s76ldob_q"/><path class="bp242uqss clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:info-standard-line" {...props}></Icon>
