<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djhgdub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djhgdub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:buy-me-a-coffee" {...props}></Icon>
