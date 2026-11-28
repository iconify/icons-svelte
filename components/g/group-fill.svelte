<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6boo9b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c6boo9b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:group-fill" {...props}></Icon>
