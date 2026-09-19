<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opvy2zb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="opvy2zb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:balloon-filled" {...props}></Icon>
