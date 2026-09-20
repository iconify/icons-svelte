<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs9nrxbwo.css';
import '../../css/i/ifixufl1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs9nrxbwo"/><path class="ifixufl1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nginx" {...props}></Icon>
