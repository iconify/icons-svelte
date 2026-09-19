<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqiy_7vqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jqiy_7vqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:phone-flip" {...props}></Icon>
