<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww6kmx10n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ww6kmx10n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:art-gallery" {...props}></Icon>
