<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7o3anbvb.css';
import '../../css/m/mgn5404zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="m7o3anbvb"/><path class="mgn5404zj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-dermatology" {...props}></Icon>
