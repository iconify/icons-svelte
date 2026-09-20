<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b843g70yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b843g70yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:book-open-text" {...props}></Icon>
