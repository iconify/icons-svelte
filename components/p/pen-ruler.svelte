<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5i22bb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r5i22bb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pen-ruler" {...props}></Icon>
