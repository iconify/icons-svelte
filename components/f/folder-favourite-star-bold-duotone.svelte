<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhc69fbif.css';
import '../../css/d/dypfpfkbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhc69fbif"/><path class="dypfpfkbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favourite-star-bold-duotone" {...props}></Icon>
