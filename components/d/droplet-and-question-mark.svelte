<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cljdfj5ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cljdfj5ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-and-question-mark" {...props}></Icon>
