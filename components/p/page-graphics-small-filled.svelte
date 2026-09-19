<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz0xrmbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rz0xrmbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-graphics-small-filled" {...props}></Icon>
