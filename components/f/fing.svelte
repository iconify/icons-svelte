<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh8shv5-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8shv5-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fing" {...props}></Icon>
