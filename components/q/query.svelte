<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs49pub-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="xs49pub-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:query" {...props}></Icon>
