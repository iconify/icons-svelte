<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1kzdpb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n1kzdpb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:comment-dollar" {...props}></Icon>
