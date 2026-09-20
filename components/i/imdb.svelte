<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clu8t7j1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="clu8t7j1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:imdb" {...props}></Icon>
