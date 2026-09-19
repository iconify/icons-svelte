<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inma3mwja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="inma3mwja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:ansible" {...props}></Icon>
