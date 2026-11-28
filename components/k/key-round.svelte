<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go_1ac-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go_1ac-5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:key-round" {...props}></Icon>
