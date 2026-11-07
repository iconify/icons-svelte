<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_0l8pw0z.css';
import '../../css/d/dt2d6ubkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_0l8pw0z"/><path class="dt2d6ubkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-snowfall-outline" {...props}></Icon>
