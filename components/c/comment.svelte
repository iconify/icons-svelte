<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpgos0b_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":676};
const content = `<path class="jpgos0b_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:comment" {...props}></Icon>
