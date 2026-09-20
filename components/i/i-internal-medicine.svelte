<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq52dvbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="aq52dvbdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-internal-medicine" {...props}></Icon>
