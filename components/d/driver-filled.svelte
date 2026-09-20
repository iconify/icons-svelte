<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wip02dbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wip02dbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:driver-filled" {...props}></Icon>
