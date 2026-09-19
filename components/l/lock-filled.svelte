<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m59fnwbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m59fnwbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:lock-filled" {...props}></Icon>
