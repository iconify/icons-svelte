<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw0nw1sey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw0nw1sey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:map-search" {...props}></Icon>
