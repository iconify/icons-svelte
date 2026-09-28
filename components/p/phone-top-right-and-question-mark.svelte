<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3z55bfbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g3z55bfbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-top-right-and-question-mark" {...props}></Icon>
