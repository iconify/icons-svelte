<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz6ij1bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz6ij1bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:reorder" {...props}></Icon>
