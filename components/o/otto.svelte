<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1xuh7khf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1xuh7khf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:otto" {...props}></Icon>
