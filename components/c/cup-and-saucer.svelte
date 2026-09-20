<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epjnci0vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="epjnci0vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cup-and-saucer" {...props}></Icon>
