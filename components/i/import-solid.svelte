<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfh-ukf2y.css';
import '../../css/q/qo-gibb2p.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 wfh-ukf2y"/><path class="clr-i-solid clr-i-solid-path-2 qo-gibb2p"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:import-solid" {...props}></Icon>
