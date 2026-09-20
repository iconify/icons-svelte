<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geeit4b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="geeit4b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:emergency-phone-14" {...props}></Icon>
