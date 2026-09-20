<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aylyq8bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aylyq8bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flame-16" {...props}></Icon>
