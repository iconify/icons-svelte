<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlrvlsb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nlrvlsb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:acmdl-square" {...props}></Icon>
