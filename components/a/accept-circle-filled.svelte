<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-rn7nb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y-rn7nb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:accept-circle-filled" {...props}></Icon>
