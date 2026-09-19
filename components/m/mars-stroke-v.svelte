<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgbheebyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1152,"height":1792};
const content = `<path class="dgbheebyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mars-stroke-v" {...props}></Icon>
