<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v155xpb1d.css';
import '../../css/x/x7ektt91o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v155xpb1d"/><path class="x7ektt91o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-care-staff-area" {...props}></Icon>
