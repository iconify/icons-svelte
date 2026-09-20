<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr4wy349f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wr4wy349f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fnac" {...props}></Icon>
