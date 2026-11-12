<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clmjnb28i.css';
import '../../css/w/waa-snbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="clmjnb28i"/><path class="waa-snbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flow-like-light" {...props}></Icon>
