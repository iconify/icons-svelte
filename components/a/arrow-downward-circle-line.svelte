<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drot4db0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drot4db0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-circle-line" {...props}></Icon>
