<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5i-nj0rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i5i-nj0rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:redo2" {...props}></Icon>
