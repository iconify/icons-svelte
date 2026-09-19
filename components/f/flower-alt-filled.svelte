<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk6zorbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk6zorbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flower-alt-filled" {...props}></Icon>
