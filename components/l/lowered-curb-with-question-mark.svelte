<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1uxt3j4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d1uxt3j4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lowered-curb-with-question-mark" {...props}></Icon>
