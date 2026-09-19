<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/almjracyr.css';
import '../../css/l/la0xxkb4z.css';
import '../../css/n/n0jc1kb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="almjracyr"/><path class="la0xxkb4z"/><path class="n0jc1kb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-security-compliance-center-workload-protection" {...props}></Icon>
