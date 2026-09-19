<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eae__35ku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eae__35ku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nose-side" {...props}></Icon>
