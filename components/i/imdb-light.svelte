<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dad-_9bln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dad-_9bln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:imdb-light" {...props}></Icon>
