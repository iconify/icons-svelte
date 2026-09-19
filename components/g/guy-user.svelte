<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggh7wdatt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":512};
const content = `<path class="ggh7wdatt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:guy-user" {...props}></Icon>
