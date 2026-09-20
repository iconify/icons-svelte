<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq7w1ubzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="dq7w1ubzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:puzzle-piece-16" {...props}></Icon>
