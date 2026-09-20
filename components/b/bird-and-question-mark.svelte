<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/by6j3h99l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="by6j3h99l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bird-and-question-mark" {...props}></Icon>
