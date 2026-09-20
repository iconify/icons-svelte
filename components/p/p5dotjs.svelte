<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpce0cc9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpce0cc9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:p5dotjs" {...props}></Icon>
