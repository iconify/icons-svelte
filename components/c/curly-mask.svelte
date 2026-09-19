<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgf-3otpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgf-3otpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:curly-mask" {...props}></Icon>
