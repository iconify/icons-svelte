<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptlw2acps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ptlw2acps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:canvasrulers" {...props}></Icon>
