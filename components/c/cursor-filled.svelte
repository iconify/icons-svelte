<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-hrygyuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-hrygyuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cursor-filled" {...props}></Icon>
