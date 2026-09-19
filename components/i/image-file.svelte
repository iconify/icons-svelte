<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spmlq2g0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="spmlq2g0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:image-file" {...props}></Icon>
