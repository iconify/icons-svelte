<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuemf_bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuemf_bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dashed-line-01" {...props}></Icon>
