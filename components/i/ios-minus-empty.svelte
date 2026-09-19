<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqy-2vh-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sqy-2vh-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-minus-empty" {...props}></Icon>
