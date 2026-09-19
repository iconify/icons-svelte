<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1rfcp77z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s1rfcp77z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:filter" {...props}></Icon>
