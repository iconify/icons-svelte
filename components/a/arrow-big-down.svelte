<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pklshbcld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pklshbcld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-big-down" {...props}></Icon>
