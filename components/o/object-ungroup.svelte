<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0fnm1bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="w0fnm1bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:object-ungroup" {...props}></Icon>
