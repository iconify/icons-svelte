<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hikmf2byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="hikmf2byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:hang-up-1-flat" {...props}></Icon>
