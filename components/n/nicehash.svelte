<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzc_g-bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzc_g-bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nicehash" {...props}></Icon>
