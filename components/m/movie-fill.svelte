<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqd6-1bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqd6-1bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-fill" {...props}></Icon>
