<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc595q_yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jc595q_yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:balloon" {...props}></Icon>
