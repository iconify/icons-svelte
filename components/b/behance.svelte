<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0-l-ecya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1344};
const content = `<path class="f0-l-ecya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:behance" {...props}></Icon>
