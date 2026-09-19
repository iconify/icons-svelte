<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdr9u_apw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gdr9u_apw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:download" {...props}></Icon>
