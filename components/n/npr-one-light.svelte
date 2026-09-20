<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj9_xabvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dj9_xabvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:npr-one-light" {...props}></Icon>
