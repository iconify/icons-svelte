<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slzdfi61y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="slzdfi61y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:imac" {...props}></Icon>
