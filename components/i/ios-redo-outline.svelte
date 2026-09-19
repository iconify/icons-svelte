<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snqeybb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="snqeybb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-redo-outline" {...props}></Icon>
