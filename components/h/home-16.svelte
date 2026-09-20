<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b80jopbwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b80jopbwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:home-16" {...props}></Icon>
