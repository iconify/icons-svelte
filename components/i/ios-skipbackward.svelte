<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8qxeskwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a8qxeskwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skipbackward" {...props}></Icon>
