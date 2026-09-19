<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu4-uvb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uu4-uvb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cloud-error" {...props}></Icon>
