<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhqt00kdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nhqt00kdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:highlighter" {...props}></Icon>
