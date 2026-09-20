<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwfft0b8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1084};
const content = `<path class="jwfft0b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mocha-light" {...props}></Icon>
