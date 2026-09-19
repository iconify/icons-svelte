<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82ck6b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j82ck6b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:h-circle" {...props}></Icon>
