<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu36pmbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eu36pmbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:project-scenarios" {...props}></Icon>
