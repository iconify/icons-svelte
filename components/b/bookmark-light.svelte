<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7d7ypsto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7d7ypsto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:bookmark-light" {...props}></Icon>
