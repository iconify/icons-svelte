<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gky-n2bzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gky-n2bzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:phone-volume" {...props}></Icon>
