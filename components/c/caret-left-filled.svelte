<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhivwlbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhivwlbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-left-filled" {...props}></Icon>
