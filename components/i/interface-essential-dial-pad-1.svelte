<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbs3f-s9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hbs3f-s9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-dial-pad-1" {...props}></Icon>
