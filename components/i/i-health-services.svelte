<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi6278x_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vi6278x_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-health-services" {...props}></Icon>
