<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yequ1mb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yequ1mb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dokploy" {...props}></Icon>
