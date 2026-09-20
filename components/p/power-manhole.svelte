<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl5jfab4x.css';
import '../../css/a/a6b9_ibtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dl5jfab4x"/><path class="a6b9_ibtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-manhole" {...props}></Icon>
