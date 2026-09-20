<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lptxm0b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lptxm0b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:falcon" {...props}></Icon>
