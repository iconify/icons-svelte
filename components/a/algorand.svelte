<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucv0ic1km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucv0ic1km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:algorand" {...props}></Icon>
