<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3dcukb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3dcukb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:android-robot" {...props}></Icon>
