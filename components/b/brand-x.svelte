<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usal9-nwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usal9-nwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:brand-x" {...props}></Icon>
