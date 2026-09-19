<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfdjb0b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mfdjb0b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:obp-square" {...props}></Icon>
