<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5blcbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xd5blcbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bus-night-filled" {...props}></Icon>
