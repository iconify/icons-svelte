<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foj66g2rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="foj66g2rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:quarter-circle" {...props}></Icon>
