<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hshqtwb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hshqtwb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:helicopter" {...props}></Icon>
