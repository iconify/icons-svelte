<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je97gj2zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="je97gj2zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-play-circle" {...props}></Icon>
