<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2j5eub2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d2j5eub2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:people-line" {...props}></Icon>
