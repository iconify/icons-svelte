<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k44ryia2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k44ryia2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:printer-3d" {...props}></Icon>
