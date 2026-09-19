<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koq8s9beh.css';
import '../../css/k/kpiwvfbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="koq8s9beh"/><path class="kpiwvfbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-app-id" {...props}></Icon>
