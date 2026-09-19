<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfpgr78hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfpgr78hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-left-square-filled" {...props}></Icon>
