<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvq0_2bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvq0_2bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:cog" {...props}></Icon>
