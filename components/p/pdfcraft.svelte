<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff5t4wldt.css';
import '../../css/w/ww30y30st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ff5t4wldt"/><path class="ww30y30st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfcraft" {...props}></Icon>
