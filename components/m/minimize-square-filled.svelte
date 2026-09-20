<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8mn5qwgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8mn5qwgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minimize-square-filled" {...props}></Icon>
