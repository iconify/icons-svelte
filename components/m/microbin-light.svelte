<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brjcgabgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brjcgabgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microbin-light" {...props}></Icon>
