<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed4eppq-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ed4eppq-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:center-focus-weak" {...props}></Icon>
