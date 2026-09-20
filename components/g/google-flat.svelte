<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2yvi0b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="f2yvi0b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:google-flat" {...props}></Icon>
