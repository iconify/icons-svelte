<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hitd8xbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hitd8xbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-trending-down" {...props}></Icon>
