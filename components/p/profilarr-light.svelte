<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo8oo-9-t.css';
import '../../css/h/h3xx9zf8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fo8oo-9-t"/><path class="h3xx9zf8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:profilarr-light" {...props}></Icon>
