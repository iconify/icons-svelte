<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r03xqicbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r03xqicbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:apple-check" {...props}></Icon>
