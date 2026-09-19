<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igwhek31a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="igwhek31a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-federated-api-management" {...props}></Icon>
