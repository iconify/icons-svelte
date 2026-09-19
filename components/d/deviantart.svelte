<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqydd_blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":24};
const content = `<path class="pqydd_blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:deviantart" {...props}></Icon>
