<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nerf759of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="nerf759of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:leaf" {...props}></Icon>
