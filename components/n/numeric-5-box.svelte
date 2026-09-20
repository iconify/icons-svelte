<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgodc5u1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgodc5u1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-5-box" {...props}></Icon>
