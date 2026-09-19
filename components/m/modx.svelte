<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r605gn10z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1792};
const content = `<path class="r605gn10z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:modx" {...props}></Icon>
