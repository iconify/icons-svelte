<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybni8x36i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ybni8x36i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-sort-h-filled" {...props}></Icon>
