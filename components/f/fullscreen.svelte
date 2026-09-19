<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8np1bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ar8np1bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:fullscreen" {...props}></Icon>
