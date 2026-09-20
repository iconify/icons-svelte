<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu3u76b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fu3u76b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rotten-tomatoes-light" {...props}></Icon>
