<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqq1feb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqq1feb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:receive-square4-filled" {...props}></Icon>
