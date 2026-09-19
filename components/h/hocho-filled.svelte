<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkdn7u2si.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xkdn7u2si"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hocho-filled" {...props}></Icon>
