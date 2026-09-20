<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv13ywbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv13ywbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keep" {...props}></Icon>
