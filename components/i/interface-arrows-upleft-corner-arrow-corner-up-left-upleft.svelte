<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tulnqjltw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tulnqjltw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-upleft-corner-arrow-corner-up-left-upleft" {...props}></Icon>
