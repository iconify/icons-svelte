<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6lc5xboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6lc5xboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:centris-four" {...props}></Icon>
