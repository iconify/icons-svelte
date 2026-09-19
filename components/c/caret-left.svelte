<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1gohd0xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e1gohd0xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:caret-left" {...props}></Icon>
