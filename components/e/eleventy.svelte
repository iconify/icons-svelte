<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm6uwybpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cm6uwybpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:eleventy" {...props}></Icon>
