<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd8eg6pwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jd8eg6pwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pause-circle-o" {...props}></Icon>
