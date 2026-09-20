<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgd551a4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgd551a4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bow-tie" {...props}></Icon>
