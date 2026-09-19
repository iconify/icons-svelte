<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klhx1xbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="klhx1xbih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:binoculars" {...props}></Icon>
