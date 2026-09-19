<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7t1_jb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t7t1_jb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:book-open-stroke-12" {...props}></Icon>
