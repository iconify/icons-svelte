<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg4u5sbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg4u5sbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-down-left-solid" {...props}></Icon>
