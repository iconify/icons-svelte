<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7auwxbuh.css';
import '../../css/b/bw3v4wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7auwxbuh"/><path class="bw3v4wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-party" {...props}></Icon>
