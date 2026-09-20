<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usd388bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="usd388bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitea-light" {...props}></Icon>
