<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtd7c6khm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtd7c6khm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-filled" {...props}></Icon>
