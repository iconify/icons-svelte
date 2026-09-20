<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjk26-b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjk26-b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:nike" {...props}></Icon>
