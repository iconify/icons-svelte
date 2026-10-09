<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxp23q9lf.css';
import '../../css/k/krkae6dal.css';
import '../../css/k/k86basb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gxp23q9lf"/><path class="krkae6dal"/><path class="k86basb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-call-48" {...props}></Icon>
