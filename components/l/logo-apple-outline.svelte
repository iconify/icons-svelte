<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9rpk5b8h.css';
import '../../css/y/yt58xlb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9rpk5b8h"/><path class="yt58xlb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-apple-outline" {...props}></Icon>
