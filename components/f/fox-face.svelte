<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9g07hbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="z9g07hbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:fox-face" {...props}></Icon>
