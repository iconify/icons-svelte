<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scbj5ebxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scbj5ebxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:movie-filter" {...props}></Icon>
