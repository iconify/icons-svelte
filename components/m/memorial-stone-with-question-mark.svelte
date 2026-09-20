<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4knz0mmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r4knz0mmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-question-mark" {...props}></Icon>
