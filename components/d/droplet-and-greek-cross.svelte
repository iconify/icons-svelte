<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbc27ibpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nbc27ibpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-and-greek-cross" {...props}></Icon>
