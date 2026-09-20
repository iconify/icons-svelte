<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at3xiib2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="at3xiib2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:publish-document" {...props}></Icon>
