<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyo8u5bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tyo8u5bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face2-small-filled" {...props}></Icon>
