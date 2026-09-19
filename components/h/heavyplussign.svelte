<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj507b3rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jj507b3rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:heavyplussign" {...props}></Icon>
