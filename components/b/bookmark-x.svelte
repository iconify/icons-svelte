<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byamri8or.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byamri8or"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bookmark-x" {...props}></Icon>
