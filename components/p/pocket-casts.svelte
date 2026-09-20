<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieasjfbcb.css';
import '../../css/d/d4shuvlgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ieasjfbcb"/><path class="d4shuvlgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-casts" {...props}></Icon>
