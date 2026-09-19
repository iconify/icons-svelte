<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7kl-imdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="l7kl-imdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-hotel" {...props}></Icon>
