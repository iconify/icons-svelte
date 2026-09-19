<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7lqgabtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="b7lqgabtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:dribbble" {...props}></Icon>
