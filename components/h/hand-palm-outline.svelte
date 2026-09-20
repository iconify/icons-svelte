<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx_6_7f8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx_6_7f8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-palm-outline" {...props}></Icon>
