<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3u1f3bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u3u1f3bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:contract" {...props}></Icon>
