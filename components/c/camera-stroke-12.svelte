<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smiam64jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="smiam64jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:camera-stroke-12" {...props}></Icon>
