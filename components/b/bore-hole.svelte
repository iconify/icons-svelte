<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sra7f7p_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sra7f7p_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bore-hole" {...props}></Icon>
