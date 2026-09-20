<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfwyp2mkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfwyp2mkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:gmee" {...props}></Icon>
