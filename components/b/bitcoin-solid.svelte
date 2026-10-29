<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjq0dtskx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wjq0dtskx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bitcoin-solid" {...props}></Icon>
