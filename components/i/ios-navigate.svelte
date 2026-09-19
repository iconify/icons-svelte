<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6d2jrb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b6d2jrb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-navigate" {...props}></Icon>
