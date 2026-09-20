<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfrgkwb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfrgkwb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pangolin" {...props}></Icon>
