<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xanmli5fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xanmli5fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:buildings5-filled" {...props}></Icon>
