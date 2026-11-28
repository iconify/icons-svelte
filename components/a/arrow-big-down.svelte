<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm2g61bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm2g61bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-big-down" {...props}></Icon>
