<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shbl2zbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="shbl2zbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:barcode" {...props}></Icon>
