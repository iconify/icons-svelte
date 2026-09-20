<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-gdiibpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-gdiibpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitify" {...props}></Icon>
