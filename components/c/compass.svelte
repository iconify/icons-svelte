<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4-a0lh9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="d4-a0lh9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:compass" {...props}></Icon>
