<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytw7gbsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":655,"height":674};
const content = `<path class="fytw7gbsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:google" {...props}></Icon>
