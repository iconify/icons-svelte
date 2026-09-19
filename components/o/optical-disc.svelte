<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iut_f7bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="iut_f7bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:optical-disc" {...props}></Icon>
