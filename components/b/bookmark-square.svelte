<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv26jd01x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tv26jd01x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:bookmark-square" {...props}></Icon>
