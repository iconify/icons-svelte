<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx9-6wbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx9-6wbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-k3os-dark" {...props}></Icon>
